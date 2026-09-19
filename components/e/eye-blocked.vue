<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le-kwnbxs.css';
import '../../css/v/ven4ce_vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="le-kwnbxs"/><path class="ven4ce_vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:eye-blocked" /></template>
