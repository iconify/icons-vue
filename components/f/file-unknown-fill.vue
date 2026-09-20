<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfnma4bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfnma4bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-unknown-fill" /></template>
