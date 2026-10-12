<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3y55cchp.css';
import '../../css/r/rkfducbyk.css';
import '../../css/v/vk46ucctf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s3y55cchp"/><path class="rkfducbyk"/><path class="vk46ucctf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:abacus-20" /></template>
