<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m51pp1z2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1792};
const content = `<path class="m51pp1z2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:dollar" /></template>
