<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz9ohguhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz9ohguhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dexe" /></template>
