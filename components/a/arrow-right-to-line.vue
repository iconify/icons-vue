<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caf2-sbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caf2-sbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-right-to-line" /></template>
