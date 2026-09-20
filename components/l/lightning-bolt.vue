<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uynm4kapm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uynm4kapm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:lightning-bolt" /></template>
