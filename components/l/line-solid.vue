<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhv7ffbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhv7ffbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:line-solid" /></template>
