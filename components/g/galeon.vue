<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmf1vnzxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmf1vnzxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:galeon" /></template>
