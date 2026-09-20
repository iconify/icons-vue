<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwyekn-8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jwyekn-8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree-beside-oval-broadleaved-tree" /></template>
