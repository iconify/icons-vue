<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c16b3xbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c16b3xbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-panel-top-filled" /></template>
