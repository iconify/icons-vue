<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/ioeul3y3v.css';
import '../../css/w/w65t7vpsn.css';
import '../../css/d/dos_yhbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ioeul3y3v"/><circle class="w65t7vpsn"/><circle class="dos_yhbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:git-branch" /></template>
