<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm-n87bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nm-n87bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:book-open-reader" /></template>
