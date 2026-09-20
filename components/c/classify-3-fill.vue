<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usus0y30x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usus0y30x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-3-fill" /></template>
