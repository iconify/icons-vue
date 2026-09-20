<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjm-hbczb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rjm-hbczb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:compiling-filled" /></template>
