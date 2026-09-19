<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1jd9vhko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="y1jd9vhko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:accounts-alt" /></template>
