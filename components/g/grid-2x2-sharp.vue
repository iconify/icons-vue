<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8-yow--l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8-yow--l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-sharp" /></template>
