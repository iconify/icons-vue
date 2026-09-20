<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpcnm8v0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpcnm8v0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:amazon-line" /></template>
