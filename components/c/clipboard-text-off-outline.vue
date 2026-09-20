<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv_3ycb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv_3ycb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-text-off-outline" /></template>
