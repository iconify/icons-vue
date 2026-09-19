<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrpo3ub4o.css';
import '../../css/j/jk5lh3bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yrpo3ub4o"/><path class="jk5lh3bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-snapchat" /></template>
