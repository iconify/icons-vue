<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri13whboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ri13whboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:caffe2" /></template>
