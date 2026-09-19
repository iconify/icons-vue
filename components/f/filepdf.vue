<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0cmx46aa.css';
import '../../css/b/btx7j3qro.css';
import '../../css/k/k8x4m_bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="x0cmx46aa"/><path class="btx7j3qro"/><path class="k8x4m_bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:filepdf" /></template>
