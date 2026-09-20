<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svpwfgbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="svpwfgbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:annular-outline" /></template>
