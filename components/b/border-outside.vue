<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snv6m8axw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="snv6m8axw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-outside" /></template>
