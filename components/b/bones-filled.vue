<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4xb59g6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4xb59g6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bones-filled" /></template>
