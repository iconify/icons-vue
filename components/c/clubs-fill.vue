<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_32m667j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_32m667j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clubs-fill" /></template>
