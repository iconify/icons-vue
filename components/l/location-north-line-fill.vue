<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt0e-l7es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lt0e-l7es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:location-north-line-fill" /></template>
