<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_09j-wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":698};
const content = `<path class="rp_09j-wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:frustrate" /></template>
