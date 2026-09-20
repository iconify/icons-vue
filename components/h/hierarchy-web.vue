<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlrpkrbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlrpkrbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:hierarchy-web" /></template>
