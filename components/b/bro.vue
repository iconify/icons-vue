<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2l3pabim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2l3pabim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bro" /></template>
