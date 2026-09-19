<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5ddmwcld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v5ddmwcld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-uturn-cw-right" /></template>
