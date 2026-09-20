<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcp2txbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rcp2txbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:join" /></template>
