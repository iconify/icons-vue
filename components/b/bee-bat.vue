<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj807wb-b.css';
import '../../css/t/t8ed8cb_k.css';
import '../../css/u/uw_-t08lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="sj807wb-b"/><circle class="t8ed8cb_k"/><path class="uw_-t08lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bee-bat" /></template>
