<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osz9gpblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osz9gpblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-restaurant" /></template>
