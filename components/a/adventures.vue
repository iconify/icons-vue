<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp1g0i7no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zp1g0i7no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:adventures" /></template>
