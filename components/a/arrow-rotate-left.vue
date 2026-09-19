<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2dgm9bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c2dgm9bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-rotate-left" /></template>
