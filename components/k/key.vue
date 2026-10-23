<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9_c1hoau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9_c1hoau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:key" /></template>
