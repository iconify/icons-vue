<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbc1rkbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wbc1rkbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:aries" /></template>
