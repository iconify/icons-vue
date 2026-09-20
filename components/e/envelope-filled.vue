<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1xu5s72o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i1xu5s72o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:envelope-filled" /></template>
