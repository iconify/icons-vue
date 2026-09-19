<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi9p0vbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi9p0vbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevron-up-circle" /></template>
