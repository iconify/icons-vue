<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9s8d-b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9s8d-b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:filter" /></template>
