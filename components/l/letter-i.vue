<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0bc0wzfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0bc0wzfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i" /></template>
