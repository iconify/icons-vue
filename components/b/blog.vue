<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gum_hnbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gum_hnbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:blog" /></template>
