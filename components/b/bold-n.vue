<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmca2ccre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tmca2ccre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-n" /></template>
