<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjp33xwpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjp33xwpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:crown-3" /></template>
