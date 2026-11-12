<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azu-vgb0r.css';
import '../../css/l/lylvmeb0j.css';
import '../../css/r/rp7_rdbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azu-vgb0r"/><path class="lylvmeb0j"/><path class="rp7_rdbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chorizard-light" /></template>
