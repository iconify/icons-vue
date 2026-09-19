<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk25przvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1280};
const content = `<path class="yk25przvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:angle-up" /></template>
