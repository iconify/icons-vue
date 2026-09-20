<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcuwd4bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qcuwd4bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crates-under-roof" /></template>
