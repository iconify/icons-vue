<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3k4x7c1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3k4x7c1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cd-broken" /></template>
