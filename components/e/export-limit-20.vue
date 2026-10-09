<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io2eiemnh.css';
import '../../css/u/uxhgw2beg.css';
import '../../css/w/weytrjnhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="io2eiemnh"/><path class="uxhgw2beg"/><path class="weytrjnhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:export-limit-20" /></template>
