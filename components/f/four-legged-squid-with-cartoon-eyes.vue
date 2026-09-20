<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-7487brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p-7487brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-legged-squid-with-cartoon-eyes" /></template>
