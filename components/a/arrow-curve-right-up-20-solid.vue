<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpsjg6mpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mpsjg6mpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-right-up-20-solid" /></template>
