<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlmme1c1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlmme1c1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-up-right-from-square" /></template>
