<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-zp17bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="o-zp17bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bone-solid" /></template>
