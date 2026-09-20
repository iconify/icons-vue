<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfbvl-1qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="jfbvl-1qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:closed-access" /></template>
