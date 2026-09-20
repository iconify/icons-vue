<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfof2l2hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfof2l2hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-error" /></template>
