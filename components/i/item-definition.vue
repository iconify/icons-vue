<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_wdpnb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o_wdpnb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:item-definition" /></template>
