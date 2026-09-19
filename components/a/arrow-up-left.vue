<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiadxcc-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiadxcc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-left" /></template>
