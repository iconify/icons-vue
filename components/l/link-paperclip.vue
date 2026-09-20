<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-alys4rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-alys4rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:link-paperclip" /></template>
