<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pudx87x2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pudx87x2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:codepen" /></template>
