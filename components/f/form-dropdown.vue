<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftk_62bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftk_62bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:form-dropdown" /></template>
