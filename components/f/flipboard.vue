<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9pbjibca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="v9pbjibca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:flipboard" /></template>
