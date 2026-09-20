<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_w_2druv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t_w_2druv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cloud-sun" /></template>
