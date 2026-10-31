<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgu_qf8mr.css';
import '../../css/d/dz--kkbng.css';
import '../../css/w/wj8_6-ths.css';
import '../../css/k/kgq3d9qlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="fgu_qf8mr"/><path class="dz--kkbng"/><path class="wj8_6-ths"/><path class="kgq3d9qlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:ghana" /></template>
