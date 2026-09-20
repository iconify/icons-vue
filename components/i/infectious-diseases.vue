<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fojrlp28i.css';
import '../../css/j/jfv0gyb_j.css';
import '../../css/r/rkoocsb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fojrlp28i"/><path class="jfv0gyb_j"/><path class="rkoocsb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:infectious-diseases" /></template>
