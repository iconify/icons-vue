<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crpcihb-l.css';
import '../../css/k/k1v5xj0bd.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="crpcihb-l"/><path class="k1v5xj0bd"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:invoice-paid-48" /></template>
