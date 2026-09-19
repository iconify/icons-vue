<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnhtjtfld.css';
import '../../css/o/ovp4s65sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nnhtjtfld"/><path class="ovp4s65sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:drawer" /></template>
