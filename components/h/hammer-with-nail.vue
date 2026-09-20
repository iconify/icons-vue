<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuehshduq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yuehshduq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hammer-with-nail" /></template>
