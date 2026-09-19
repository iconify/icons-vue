<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evq328bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="evq328bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-kiss" /></template>
