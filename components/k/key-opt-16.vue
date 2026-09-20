<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8famm2mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n8famm2mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:key-opt-16" /></template>
