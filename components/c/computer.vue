<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y58ycfb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="y58ycfb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:computer" /></template>
