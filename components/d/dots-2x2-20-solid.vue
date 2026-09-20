<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk0g2vbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mk0g2vbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x2-20-solid" /></template>
