<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp3l25kpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zp3l25kpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:log-in-sharp" /></template>
