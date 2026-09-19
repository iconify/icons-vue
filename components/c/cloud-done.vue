<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tybfk_b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tybfk_b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cloud-done" /></template>
