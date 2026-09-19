<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy9u_gbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hy9u_gbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrows-rotate-right" /></template>
