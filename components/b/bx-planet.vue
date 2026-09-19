<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nytgl6bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nytgl6bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-planet" /></template>
