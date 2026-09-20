<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnqa97brp.css';
import '../../css/b/bm4a6ibol.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cnqa97brp"/><path class="bm4a6ibol"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-somalia" /></template>
