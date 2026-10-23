<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5n2x1bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5n2x1bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:folder-archive" /></template>
