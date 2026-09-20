<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axuo-63qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axuo-63qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bnt" /></template>
