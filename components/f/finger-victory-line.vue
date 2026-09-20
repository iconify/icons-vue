<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra3zzfhcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra3zzfhcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-victory-line" /></template>
