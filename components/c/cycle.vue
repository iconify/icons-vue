<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrc89m55w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wrc89m55w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:cycle" /></template>
