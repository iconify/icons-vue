<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsa7ajhsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsa7ajhsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coins" /></template>
