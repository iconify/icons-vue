<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i55nj8tdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i55nj8tdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:good-two" /></template>
