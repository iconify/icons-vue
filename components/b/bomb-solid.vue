<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr-qqzwxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr-qqzwxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bomb-solid" /></template>
