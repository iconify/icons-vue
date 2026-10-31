<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffq2y69hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffq2y69hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-down-up" /></template>
