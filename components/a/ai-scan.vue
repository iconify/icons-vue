<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp975jbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp975jbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-scan" /></template>
