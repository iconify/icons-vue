<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st6matk8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1728};
const content = `<path class="st6matk8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:long-arrow-up" /></template>
