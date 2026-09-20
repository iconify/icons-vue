<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvo1e4bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvo1e4bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-check" /></template>
