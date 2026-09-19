<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nea67geye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nea67geye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:good-one" /></template>
