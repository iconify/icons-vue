<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4f4hpsrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4f4hpsrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:document-3-line" /></template>
