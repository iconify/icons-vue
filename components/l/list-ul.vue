<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9qgd3b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9qgd3b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:list-ul" /></template>
