<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4my-sbai.css';
import '../../css/j/ja6qjjbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4my-sbai"/><path class="ja6qjjbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-opened-bold" /></template>
