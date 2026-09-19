<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llog1wgkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":469,"height":512};
const content = `<path class="llog1wgkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:caffe" /></template>
