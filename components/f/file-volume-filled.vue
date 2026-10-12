<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj896_brl.css';
import '../../css/j/j22w93are.css';
import '../../css/q/qcswzebnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj896_brl"/><path class="j22w93are"/><path class="qcswzebnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-volume-filled" /></template>
