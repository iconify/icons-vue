<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh1tldhks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fh1tldhks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-down" /></template>
