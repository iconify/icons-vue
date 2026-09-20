<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfw64ib8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pfw64ib8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:globe" /></template>
