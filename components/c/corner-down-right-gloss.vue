<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb166jh2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb166jh2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-down-right-gloss" /></template>
