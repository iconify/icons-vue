<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anjpc_b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anjpc_b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-code-corner-fill" /></template>
