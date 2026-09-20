<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_f49x26x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l_f49x26x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:lightning-filled" /></template>
