<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w456m38wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w456m38wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:contao" /></template>
