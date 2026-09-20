<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijt4jib4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijt4jib4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:codefactor-logo-solid" /></template>
