<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg-t_fezd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kg-t_fezd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h1-20-solid" /></template>
