<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhn7bjbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hhn7bjbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-down-right-box" /></template>
