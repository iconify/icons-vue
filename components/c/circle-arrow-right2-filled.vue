<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu4n2224j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu4n2224j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-right2-filled" /></template>
