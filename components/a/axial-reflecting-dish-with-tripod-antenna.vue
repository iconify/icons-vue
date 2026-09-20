<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3zkh7vhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u3zkh7vhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:axial-reflecting-dish-with-tripod-antenna" /></template>
