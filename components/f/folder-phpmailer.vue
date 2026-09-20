<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiap8ebun.css';
import '../../css/o/o1kvkvbiz.css';
import '../../css/n/n2y8m9bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aiap8ebun"/><path class="o1kvkvbiz"/><path class="n2y8m9bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-phpmailer" /></template>
