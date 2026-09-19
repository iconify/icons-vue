<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-ygl7brj.css';
import '../../css/d/dc-p_7bld.css';
import '../../css/i/iehx50jjq.css';
import '../../css/h/hnm18mbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-ygl7brj"/><circle class="dc-p_7bld"/><circle class="iehx50jjq"/><circle class="hnm18mbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chatbox-ellipses-outline" /></template>
