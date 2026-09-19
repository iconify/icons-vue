<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1ze04blp.css';
import '../../css/d/doshyacby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1ze04blp"/><path class="doshyacby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layers-alt-filled" /></template>
