<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5jj_uqmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s5jj_uqmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:euro-sign" /></template>
