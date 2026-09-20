<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjskbi9oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjskbi9oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-slice-1" /></template>
