<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lszm1acwc.css';
import '../../css/a/aqnwi5bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lszm1acwc"/><path class="aqnwi5bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-aws" /></template>
