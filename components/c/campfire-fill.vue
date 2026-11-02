<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsu2-fabk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsu2-fabk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:campfire-fill" /></template>
