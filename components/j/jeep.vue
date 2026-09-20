<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-nsp2j0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c-nsp2j0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jeep" /></template>
