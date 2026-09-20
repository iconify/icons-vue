<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grfwzfblc.css';
import '../../css/u/uszi3vbgi.css';
import '../../css/j/j3bk5ybiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grfwzfblc"/><path class="uszi3vbgi"/><path clip-rule="evenodd" class="j3bk5ybiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bcube" /></template>
