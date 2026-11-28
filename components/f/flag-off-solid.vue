<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-c0-2jci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-c0-2jci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flag-off-solid" /></template>
