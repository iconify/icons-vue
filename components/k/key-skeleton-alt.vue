<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiq3o6eix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiq3o6eix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:key-skeleton-alt" /></template>
