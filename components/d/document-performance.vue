<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zri2zabea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zri2zabea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-performance" /></template>
