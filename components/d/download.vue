<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubi-bbbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubi-bbbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:download" /></template>
