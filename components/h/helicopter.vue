<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ws6he8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="x5ws6he8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:helicopter" /></template>
