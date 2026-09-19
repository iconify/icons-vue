<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne3jv2bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ne3jv2bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hexagonal" /></template>
