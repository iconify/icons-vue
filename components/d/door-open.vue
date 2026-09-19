<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5aho55cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1216,"height":2016};
const content = `<path class="h5aho55cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:door-open" /></template>
