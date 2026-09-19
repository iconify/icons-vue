<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywize-p9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywize-p9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:desk-for-laptop" /></template>
