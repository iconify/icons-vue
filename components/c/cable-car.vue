<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syuj88pod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syuj88pod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cable-car" /></template>
