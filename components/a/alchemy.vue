<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1-yl58zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1-yl58zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alchemy" /></template>
