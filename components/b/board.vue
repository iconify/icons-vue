<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chnsk5b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chnsk5b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:board" /></template>
