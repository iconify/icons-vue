<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxuuc5wmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxuuc5wmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dock" /></template>
