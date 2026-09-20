<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf9m077hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf9m077hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cursor-move" /></template>
