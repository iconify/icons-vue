<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsg1p1yyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsg1p1yyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory-open-fill-24" /></template>
