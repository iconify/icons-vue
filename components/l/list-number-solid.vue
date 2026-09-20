<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvm0zswmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvm0zswmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:list-number-solid" /></template>
