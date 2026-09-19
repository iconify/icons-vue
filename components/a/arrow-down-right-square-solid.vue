<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlg3zzljz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlg3zzljz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-down-right-square-solid" /></template>
