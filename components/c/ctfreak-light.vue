<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r83c7_5hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r83c7_5hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ctfreak-light" /></template>
