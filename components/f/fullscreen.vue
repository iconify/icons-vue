<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhab1oxmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhab1oxmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:fullscreen" /></template>
