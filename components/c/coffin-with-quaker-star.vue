<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4v7wtbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y4v7wtbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffin-with-quaker-star" /></template>
