<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5lure36s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h5lure36s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-down-16-solid" /></template>
