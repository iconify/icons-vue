<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbej-b2vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lbej-b2vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:formula" /></template>
