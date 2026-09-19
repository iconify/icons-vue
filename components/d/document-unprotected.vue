<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyolqcc_l.css';
import '../../css/s/s28o31bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yyolqcc_l"/><path class="s28o31bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-unprotected" /></template>
