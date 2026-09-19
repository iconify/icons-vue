<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppom3knrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ppom3knrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:less-than" /></template>
