<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h868vpbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h868vpbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-left-circle-solid" /></template>
