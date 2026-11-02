<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s23ly6bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s23ly6bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:haze-fill" /></template>
