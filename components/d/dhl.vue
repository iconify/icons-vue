<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze9alyjfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ze9alyjfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:dhl" /></template>
