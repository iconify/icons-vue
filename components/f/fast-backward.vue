<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0ni1ku-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="n0ni1ku-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:fast-backward" /></template>
