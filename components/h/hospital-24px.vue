<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrk4ij8ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jrk4ij8ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hospital-24px" /></template>
