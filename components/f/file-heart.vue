<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paika9b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paika9b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-heart" /></template>
