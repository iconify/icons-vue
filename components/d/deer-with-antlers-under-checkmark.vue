<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmlnxjsdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kmlnxjsdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:deer-with-antlers-under-checkmark" /></template>
