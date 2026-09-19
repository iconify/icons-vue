<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-7_1mb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k-7_1mb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:funnel-solid" /></template>
