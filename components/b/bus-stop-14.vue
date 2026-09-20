<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-vayiz0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="z-vayiz0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:bus-stop-14" /></template>
