<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl-vz6ykx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl-vz6ykx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-zip-line" /></template>
