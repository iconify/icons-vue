<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv2_brboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rv2_brboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-code" /></template>
