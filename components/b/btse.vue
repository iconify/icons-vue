<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0s2u9bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0s2u9bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btse" /></template>
