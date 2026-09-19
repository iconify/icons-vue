<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl_3kfblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sl_3kfblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-library-16-solid" /></template>
