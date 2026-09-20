<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azd3_ibmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azd3_ibmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-right-top" /></template>
