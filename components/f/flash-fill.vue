<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dal7ae8el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dal7ae8el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flash-fill" /></template>
