<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp7kmub6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp7kmub6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:key" /></template>
