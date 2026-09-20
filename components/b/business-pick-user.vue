<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6ukjobns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6ukjobns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:business-pick-user" /></template>
