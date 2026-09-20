<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a64e_yb6y.css';
import '../../css/u/uygqtsbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="a64e_yb6y"/><path class="uygqtsbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:double-curly-loop" /></template>
