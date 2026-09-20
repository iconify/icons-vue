<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaeycfbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaeycfbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:head-side-cough" /></template>
