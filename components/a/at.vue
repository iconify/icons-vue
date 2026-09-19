<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujtkal8vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ujtkal8vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:at" /></template>
