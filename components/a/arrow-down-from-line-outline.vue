<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl21u1gxg.css';
import '../../css/m/mhkgzbcsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl21u1gxg"/><path class="mhkgzbcsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-down-from-line-outline" /></template>
