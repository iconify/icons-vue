<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkm7mbckp.css';
import '../../css/s/s4uphz44s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkm7mbckp"/><path class="s4uphz44s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:leetcode" /></template>
