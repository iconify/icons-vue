<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnu9rbbvf.css';
import '../../css/h/hezf90bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnu9rbbvf"/><path class="hezf90bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:hd" /></template>
