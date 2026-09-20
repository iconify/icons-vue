<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-e-l3k7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-e-l3k7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:add" /></template>
