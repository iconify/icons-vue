<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv8z7nfju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv8z7nfju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left3-filled" /></template>
