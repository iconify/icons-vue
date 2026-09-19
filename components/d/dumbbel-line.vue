<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgtyx9bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xgtyx9bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dumbbel-line" /></template>
