<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r290_pbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r290_pbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-right-up" /></template>
