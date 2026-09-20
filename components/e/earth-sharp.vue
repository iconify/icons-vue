<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asc4s_bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asc4s_bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earth-sharp" /></template>
