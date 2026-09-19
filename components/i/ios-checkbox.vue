<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st9mc6zjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="st9mc6zjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-checkbox" /></template>
