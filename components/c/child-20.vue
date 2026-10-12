<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez22xh-gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ez22xh-gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:child-20" /></template>
