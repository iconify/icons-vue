<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrticffib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrticffib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dashboard-24" /></template>
