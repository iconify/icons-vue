<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7o_thdxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b7o_thdxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:head-side-cough" /></template>
