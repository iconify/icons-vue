<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji9sdpzom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ji9sdpzom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:album-2-fill" /></template>
