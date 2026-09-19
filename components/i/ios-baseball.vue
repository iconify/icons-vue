<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udcbvob3v.css';
import '../../css/l/l_nfrbb_z.css';
import '../../css/r/r-n9oxbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="udcbvob3v"/><path class="l_nfrbb_z"/><path class="r-n9oxbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-baseball" /></template>
