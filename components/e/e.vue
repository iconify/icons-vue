<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bltctjbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":559,"height":671};
const content = `<path class="bltctjbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:e" /></template>
