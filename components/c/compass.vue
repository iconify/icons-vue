<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp9hcv0mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mp9hcv0mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:compass" /></template>
