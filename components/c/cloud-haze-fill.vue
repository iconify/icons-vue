<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x33k3_bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x33k3_bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-haze-fill" /></template>
