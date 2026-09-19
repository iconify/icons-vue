<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjv214_sf.css';
import '../../css/j/j87t2qbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wjv214_sf"/><path class="j87t2qbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:delivery-parcel" /></template>
