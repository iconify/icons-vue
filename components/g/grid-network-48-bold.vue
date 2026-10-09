<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz0_wjbxg.css';
import '../../css/a/aeebr_bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sz0_wjbxg"/><path class="aeebr_bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-network-48-bold" /></template>
