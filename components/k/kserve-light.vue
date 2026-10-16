<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh4dfy4zb.css';
import '../../css/v/v-ne-abrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yh4dfy4zb"/><path class="cls-2 v-ne-abrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kserve-light" /></template>
