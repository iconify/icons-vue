<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_3ujp46z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t_3ujp46z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:comments-dollar" /></template>
