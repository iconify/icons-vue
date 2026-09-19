<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy9xnhbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yy9xnhbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:id-alt" /></template>
