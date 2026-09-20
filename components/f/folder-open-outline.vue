<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km69o8ksh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="km69o8ksh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-open-outline" /></template>
