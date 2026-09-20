<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mejt4lx3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mejt4lx3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-graph-filled" /></template>
