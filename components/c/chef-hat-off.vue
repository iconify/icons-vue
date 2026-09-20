<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrmpk4ctg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrmpk4ctg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chef-hat-off" /></template>
