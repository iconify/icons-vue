<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf_9qvbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf_9qvbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:graphql" /></template>
