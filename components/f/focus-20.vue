<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcv3kkbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xcv3kkbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:focus-20" /></template>
