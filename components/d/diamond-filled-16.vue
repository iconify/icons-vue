<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9a-29sdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9a-29sdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:diamond-filled-16" /></template>
