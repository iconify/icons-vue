<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cze689t2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cze689t2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:at" /></template>
