<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv_llbcob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bv_llbcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:cath-lab" /></template>
