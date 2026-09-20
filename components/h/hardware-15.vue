<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w17b5e_rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w17b5e_rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:hardware-15" /></template>
