<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv1o4ubmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mv1o4ubmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-down-right-20-solid" /></template>
