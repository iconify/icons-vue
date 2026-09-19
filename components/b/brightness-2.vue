<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6re6s5_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":432};
const content = `<path class="t6re6s5_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brightness-2" /></template>
