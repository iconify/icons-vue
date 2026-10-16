<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loa2wvbos.css';
import '../../css/a/a2tuuobyg.css';
import '../../css/w/wv3plmbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="loa2wvbos"/><path class="a2tuuobyg"/><path class="wv3plmbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cctv-20-bold" /></template>
