<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhwyy6cym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hhwyy6cym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:density-m-filled" /></template>
