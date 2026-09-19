<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0vsyfboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0vsyfboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:link" /></template>
