<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r037uibrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r037uibrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:exchange-one" /></template>
