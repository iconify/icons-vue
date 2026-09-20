<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4ocmub3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4ocmub3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-square-filled" /></template>
