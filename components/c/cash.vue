<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owr-85b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="owr-85b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:cash" /></template>
