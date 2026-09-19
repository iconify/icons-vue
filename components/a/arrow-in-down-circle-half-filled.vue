<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx4tahbow.css';
import '../../css/g/ge30ml4_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx4tahbow"/><path class="ge30ml4_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-circle-half-filled" /></template>
