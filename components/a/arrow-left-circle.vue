<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-whp-f_g.css';
import '../../css/u/ufvpeacwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="j-whp-f_g"/><path clip-rule="evenodd" class="ufvpeacwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-left-circle" /></template>
