<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8u2_nrqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="k8u2_nrqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:guidenai" /></template>
