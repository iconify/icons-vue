<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnzfn87yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnzfn87yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:intersect-fill" /></template>
