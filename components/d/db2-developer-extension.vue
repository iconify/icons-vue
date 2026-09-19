<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpfp1dycz.css';
import '../../css/c/cqm6b97dt.css';
import '../../css/r/r5yn_xycd.css';
import '../../css/a/aa_op5b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cpfp1dycz"/><path class="cqm6b97dt"/><circle class="r5yn_xycd"/><path class="aa_op5b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:db2-developer-extension" /></template>
