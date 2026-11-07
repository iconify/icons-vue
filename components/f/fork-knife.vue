<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-b1zpjvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-b1zpjvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:fork-knife" /></template>
