<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2t00mbrv.css';
import '../../css/o/oensybc-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p2t00mbrv"/><path class="oensybc-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-salt" /></template>
