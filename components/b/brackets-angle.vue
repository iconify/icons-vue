<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf3zyh2xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf3zyh2xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brackets-angle" /></template>
