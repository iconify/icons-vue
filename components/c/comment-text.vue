<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkziaacrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="xkziaacrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-text" /></template>
