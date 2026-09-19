<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul01t7oem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ul01t7oem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:kirby" /></template>
