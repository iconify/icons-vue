<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxx6f10mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxx6f10mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:bluetooth" /></template>
