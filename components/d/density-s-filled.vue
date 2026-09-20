<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf-c6_b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pf-c6_b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:density-s-filled" /></template>
