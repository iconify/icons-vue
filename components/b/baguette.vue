<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsm0-megr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsm0-megr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:baguette" /></template>
