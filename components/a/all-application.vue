<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lksn13b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lksn13b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:all-application" /></template>
