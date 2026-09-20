<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jma98wbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jma98wbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-all" /></template>
