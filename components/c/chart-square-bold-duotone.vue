<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/e/e-_t4f13s.css';
import '../../css/f/f5bh_j-5r.css';
import '../../css/c/c937-fbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="e-_t4f13s"/><path class="f5bh_j-5r"/><path class="c937-fbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-square-bold-duotone" /></template>
