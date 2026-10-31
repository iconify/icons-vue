<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c16u-3bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c16u-3bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-down-right" /></template>
