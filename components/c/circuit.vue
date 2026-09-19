<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkxahjftn.css';
import '../../css/x/xxi34xgyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hkxahjftn"/><path class="xxi34xgyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:circuit" /></template>
