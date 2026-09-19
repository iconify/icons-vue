<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpchaaclv.css';
import '../../css/b/b73r8pbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rpchaaclv"/><path class="b73r8pbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-orders" /></template>
