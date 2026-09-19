<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgpzimtyu.css';
import '../../css/b/bydz9ac_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hgpzimtyu"/><path class="bydz9ac_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-cluster-bar" /></template>
