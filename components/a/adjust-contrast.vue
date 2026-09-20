<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipm2-g_7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipm2-g_7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:adjust-contrast" /></template>
