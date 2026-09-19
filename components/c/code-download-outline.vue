<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmhge1brw.css';
import '../../css/t/t8uvlebro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmhge1brw"/><path class="t8uvlebro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:code-download-outline" /></template>
