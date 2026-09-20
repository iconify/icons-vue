<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxgef79ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jxgef79ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-snow" /></template>
