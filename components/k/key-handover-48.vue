<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd6bhzvez.css';
import '../../css/g/g81g92bif.css';
import '../../css/u/u4s52t5jm.css';
import '../../css/v/vsgt2_ggn.css';
import '../../css/b/bn-8t67hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rd6bhzvez"/><path class="g81g92bif"/><path class="u4s52t5jm"/><path class="vsgt2_ggn"/><path class="bn-8t67hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-handover-48" /></template>
