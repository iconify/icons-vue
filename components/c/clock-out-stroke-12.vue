<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1qje2naz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a1qje2naz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-out-stroke-12" /></template>
