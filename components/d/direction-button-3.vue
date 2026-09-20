<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcxr8acbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcxr8acbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:direction-button-3" /></template>
