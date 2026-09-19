<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3q3w37ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3q3w37ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bluetooth-sharp" /></template>
