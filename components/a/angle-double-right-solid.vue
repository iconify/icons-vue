<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbpolbcfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vbpolbcfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angle-double-right-solid" /></template>
