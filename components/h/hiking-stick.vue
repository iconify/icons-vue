<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrhr6tbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrhr6tbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hiking-stick" /></template>
