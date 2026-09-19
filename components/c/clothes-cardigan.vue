<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3s8gvbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v3s8gvbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:clothes-cardigan" /></template>
