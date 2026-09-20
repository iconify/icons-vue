<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re84pcc3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re84pcc3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-g" /></template>
