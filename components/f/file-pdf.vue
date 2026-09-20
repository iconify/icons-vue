<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q49xl5b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q49xl5b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:file-pdf" /></template>
