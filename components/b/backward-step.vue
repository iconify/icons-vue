<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m153w7bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="m153w7bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:backward-step" /></template>
