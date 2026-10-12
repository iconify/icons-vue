<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/xd5kflbch.css';
import '../../css/c/c8oi8ccvi.css';
import '../../css/y/yu5hcsbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xd5kflbch"/><path class="c8oi8ccvi"/><circle class="yu5hcsbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:mail-dot" /></template>
