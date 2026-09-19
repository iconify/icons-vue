<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh9roon6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mh9roon6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-arrow-up" /></template>
