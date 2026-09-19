<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0drj3h3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l0drj3h3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:evil" /></template>
