<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koggl612w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koggl612w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-down-filled" /></template>
