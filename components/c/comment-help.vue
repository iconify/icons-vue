<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riyd5ab2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riyd5ab2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-help" /></template>
