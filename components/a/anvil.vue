<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg0qq-b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zg0qq-b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:anvil" /></template>
