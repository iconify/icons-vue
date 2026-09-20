<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqn65lb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xqn65lb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bitcoin" /></template>
