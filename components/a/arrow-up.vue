<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyf3bpbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyf3bpbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:arrow-up" /></template>
