<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btv2d0blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="btv2d0blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:jar" /></template>
