<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/redq9pfak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="redq9pfak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-check" /></template>
