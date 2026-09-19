<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6_x99d5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":448};
const content = `<path class="t6_x99d5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hand-pointer-right" /></template>
