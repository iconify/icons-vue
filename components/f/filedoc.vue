<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btx7j3qro.css';
import '../../css/p/pfijng4-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="btx7j3qro"/><path class="pfijng4-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:filedoc" /></template>
