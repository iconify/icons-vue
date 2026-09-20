<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipcy7l2ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ipcy7l2ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:electric-cord-3-solid" /></template>
