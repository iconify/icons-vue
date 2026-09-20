<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puh1-6bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="puh1-6bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:inbox" /></template>
