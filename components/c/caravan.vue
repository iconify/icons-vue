<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcsdb2bla.css';
import '../../css/c/cpwldbcex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dcsdb2bla"/><path class="cpwldbcex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:caravan" /></template>
