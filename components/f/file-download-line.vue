<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqm17obfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqm17obfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-download-line" /></template>
