<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8u0u259p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8u0u259p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-open-1-filled" /></template>
