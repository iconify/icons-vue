<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8a4hlb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8a4hlb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-m" /></template>
