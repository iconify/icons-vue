<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y02gaibli.css';
import '../../css/w/wgcfbo68c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="y02gaibli"/><path class="wgcfbo68c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:antarctica" /></template>
