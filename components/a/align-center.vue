<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqmg86b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aqmg86b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:align-center" /></template>
