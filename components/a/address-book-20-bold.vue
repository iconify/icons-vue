<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2linuthc.css';
import '../../css/p/p4elc_bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p2linuthc"/><path class="p4elc_bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:address-book-20-bold" /></template>
