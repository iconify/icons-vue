<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl9p_ccsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tl9p_ccsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:gender-neutral-user" /></template>
