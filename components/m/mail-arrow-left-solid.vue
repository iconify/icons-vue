<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umjqp-bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umjqp-bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-arrow-left-solid" /></template>
