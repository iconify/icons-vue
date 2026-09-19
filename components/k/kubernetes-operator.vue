<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shykeihid.css';
import '../../css/o/ot-x0gcwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="shykeihid"/><path class="ot-x0gcwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:kubernetes-operator" /></template>
