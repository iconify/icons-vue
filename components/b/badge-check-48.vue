<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jha4hptgn.css';
import '../../css/g/gx580lbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jha4hptgn"/><path class="gx580lbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-check-48" /></template>
