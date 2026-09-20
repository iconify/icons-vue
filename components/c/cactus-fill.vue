<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reotvsbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="reotvsbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cactus-fill" /></template>
