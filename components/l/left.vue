<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syip7tkhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="syip7tkhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:left" /></template>
