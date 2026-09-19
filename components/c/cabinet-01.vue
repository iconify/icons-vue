<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2lrwachb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2lrwachb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cabinet-01" /></template>
