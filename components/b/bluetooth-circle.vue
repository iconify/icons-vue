<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3m-qj0tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3m-qj0tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bluetooth-circle" /></template>
