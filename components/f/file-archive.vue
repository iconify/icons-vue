<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/qtq3h6bch.css';
import '../../css/q/qez094buu.css';
import '../../css/w/wzga5cc5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qtq3h6bch"/><path class="qez094buu"/><circle class="wzga5cc5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:file-archive" /></template>
