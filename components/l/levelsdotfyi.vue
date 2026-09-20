<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsp0fcxhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsp0fcxhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:levelsdotfyi" /></template>
