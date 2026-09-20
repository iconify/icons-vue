<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oko2r_blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oko2r_blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-new-outline" /></template>
