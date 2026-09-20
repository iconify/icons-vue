<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh9thnbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wh9thnbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:benzene-filled" /></template>
