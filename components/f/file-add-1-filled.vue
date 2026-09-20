<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvr2fiwiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvr2fiwiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-add-1-filled" /></template>
