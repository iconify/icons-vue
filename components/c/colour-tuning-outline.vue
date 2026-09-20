<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg4mb7p2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lg4mb7p2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:colour-tuning-outline" /></template>
