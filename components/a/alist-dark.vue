<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q28-psbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q28-psbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alist-dark" /></template>
