<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ball2zbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ball2zbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:japanese-yen-gloss" /></template>
