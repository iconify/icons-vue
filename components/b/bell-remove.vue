<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyj129fbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyj129fbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bell-remove" /></template>
