<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhifhpf8r.css';
import '../../css/m/me2lh9ojh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xhifhpf8r"/><path class="me2lh9ojh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:image-reference" /></template>
