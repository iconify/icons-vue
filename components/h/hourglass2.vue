<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-6f03bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-6f03bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hourglass2" /></template>
