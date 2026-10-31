<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu_pywb_w.css';
import '../../css/d/diu_rvd7f.css';
import '../../css/s/sztat3bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nu_pywb_w"/><path class="diu_rvd7f"/><path class="sztat3bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:commonwealth-of-independent-states" /></template>
