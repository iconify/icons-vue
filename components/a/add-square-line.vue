<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7kuph5gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7kuph5gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:add-square-line" /></template>
