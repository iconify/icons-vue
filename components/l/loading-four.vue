<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn_94diua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pn_94diua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:loading-four" /></template>
