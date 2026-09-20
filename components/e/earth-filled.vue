<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r54-3ccgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r54-3ccgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:earth-filled" /></template>
