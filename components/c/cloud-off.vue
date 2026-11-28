<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu05dtbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu05dtbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-off" /></template>
