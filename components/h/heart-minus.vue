<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-92dmb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-92dmb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:heart-minus" /></template>
