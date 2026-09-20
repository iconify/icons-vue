<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmatdhbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jmatdhbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:container" /></template>
