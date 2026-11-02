<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnr__ybfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnr__ybfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-symlink-line" /></template>
