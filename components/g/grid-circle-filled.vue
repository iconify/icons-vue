<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3gp-eb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3gp-eb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-circle-filled" /></template>
