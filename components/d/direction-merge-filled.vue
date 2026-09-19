<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldjgpjbom.css';
import '../../css/c/chq_v_ohg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ldjgpjbom"/><path class="chq_v_ohg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-merge-filled" /></template>
