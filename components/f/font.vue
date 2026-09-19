<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl8_8wpxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="nl8_8wpxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:font" /></template>
