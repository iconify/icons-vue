<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii30vacbk.css';
import '../../css/f/fdr6bubwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii30vacbk"/><path class="fdr6bubwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:external-link-filled" /></template>
