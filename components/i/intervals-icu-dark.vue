<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzq2i_09v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":462.9,"height":462.9};
const content = `<path class="yzq2i_09v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:intervals-icu-dark" /></template>
