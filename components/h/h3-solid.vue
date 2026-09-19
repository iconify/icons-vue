<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psjn8qb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psjn8qb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h3-solid" /></template>
