<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu5lx12xc.css';
import '../../css/z/zla48o_aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gu5lx12xc"/><path clip-rule="evenodd" class="zla48o_aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-magnifying-glass-16-solid" /></template>
