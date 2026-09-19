<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws1-s1f7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ws1-s1f7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chair" /></template>
