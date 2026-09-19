<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhjjpdbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="vhjjpdbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:check-empty" /></template>
