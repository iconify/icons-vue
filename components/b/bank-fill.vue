<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f13g02hns.css';
import '../../css/y/y_xfi-b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f13g02hns"/><path class="y_xfi-b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bank-fill" /></template>
