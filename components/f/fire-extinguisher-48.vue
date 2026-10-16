<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m24wi8bnz.css';
import '../../css/n/ntd2yfzrm.css';
import '../../css/b/bi_k8i90y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m24wi8bnz"/><path class="ntd2yfzrm"/><path class="bi_k8i90y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-extinguisher-48" /></template>
