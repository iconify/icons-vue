<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k20xl2bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k20xl2bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:low-vision" /></template>
