<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb02qn-fy.css';
import '../../css/b/btx7j3qro.css';
import '../../css/k/k8x4m_bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="nb02qn-fy"/><path class="btx7j3qro"/><path class="k8x4m_bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:filevideo" /></template>
