<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7_yf3hsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7_yf3hsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:common-file-horizontal-bold" /></template>
