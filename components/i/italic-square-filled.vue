<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip591cb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ip591cb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:italic-square-filled" /></template>
