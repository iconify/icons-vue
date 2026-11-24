<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5jau6bgw.css';
import '../../css/j/j22w93are.css';
import '../../css/p/pndt6mbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5jau6bgw"/><path class="j22w93are"/><path class="pndt6mbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-volume-filled" /></template>
