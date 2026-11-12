<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9-d-dbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9-d-dbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dagster-light" /></template>
