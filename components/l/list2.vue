<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwrk4e1ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mwrk4e1ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:list2" /></template>
