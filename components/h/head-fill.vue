<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ifn1ljn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u8ifn1ljn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:head-fill" /></template>
