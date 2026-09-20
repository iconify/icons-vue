<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwk2iib2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwk2iib2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical-octagon-solid" /></template>
