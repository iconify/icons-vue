<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc-zz-dvu.css';
import '../../css/u/uh_772b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zc-zz-dvu"/><path class="uh_772b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-z-os-containers" /></template>
