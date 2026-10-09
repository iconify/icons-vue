<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l20v2fbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l20v2fbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coal-20" /></template>
