<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u701hrb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u701hrb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-edit" /></template>
