<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8b33yeif.css';
import '../../css/v/v7fiiyb4p.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8b33yeif"/><path clip-rule="evenodd" class="v7fiiyb4p"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-badge-filled" /></template>
