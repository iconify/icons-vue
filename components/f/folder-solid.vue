<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vef0kgbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vef0kgbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-solid" /></template>
