<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck9oiac6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ck9oiac6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:hazelnut-with-leaves" /></template>
