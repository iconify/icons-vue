<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk0nq-frr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk0nq-frr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud-moon" /></template>
