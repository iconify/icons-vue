<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz4esqtld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oz4esqtld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:calcminus" /></template>
