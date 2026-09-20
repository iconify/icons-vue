<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl7_c774e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dl7_c774e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-check2-filled" /></template>
