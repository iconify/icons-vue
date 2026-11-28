<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nin_08yup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nin_08yup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-column-big-solid" /></template>
