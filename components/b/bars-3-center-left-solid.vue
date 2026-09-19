<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuo1t367k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cuo1t367k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-center-left-solid" /></template>
