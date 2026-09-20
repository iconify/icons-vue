<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxlzprl1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlzprl1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-radius" /></template>
