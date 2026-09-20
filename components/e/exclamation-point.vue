<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqb-0_4ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xqb-0_4ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:exclamation-point" /></template>
