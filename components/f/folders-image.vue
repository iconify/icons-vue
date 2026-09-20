<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh6wf76bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh6wf76bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folders-image" /></template>
