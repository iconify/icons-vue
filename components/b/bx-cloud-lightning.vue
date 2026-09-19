<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0vzs5apr.css';
import '../../css/t/toc-9jzis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0vzs5apr"/><path class="toc-9jzis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-cloud-lightning" /></template>
