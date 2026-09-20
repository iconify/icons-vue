<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqiuyz00l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqiuyz00l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:creative-commons-line" /></template>
