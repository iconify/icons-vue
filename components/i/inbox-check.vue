<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbngkxkbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbngkxkbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:inbox-check" /></template>
