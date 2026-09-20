<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh1anqb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh1anqb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:h-5" /></template>
