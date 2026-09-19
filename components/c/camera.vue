<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zux88jbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zux88jbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:camera" /></template>
