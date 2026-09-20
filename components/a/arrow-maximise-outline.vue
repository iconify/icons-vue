<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prd1j7b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prd1j7b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-maximise-outline" /></template>
