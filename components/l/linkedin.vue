<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk-n8nb7r.css';
import '../../css/x/xizbhjbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kk-n8nb7r"/><path class="xizbhjbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkedin" /></template>
