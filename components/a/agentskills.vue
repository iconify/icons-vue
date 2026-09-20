<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaqp-z-ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaqp-z-ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:agentskills" /></template>
