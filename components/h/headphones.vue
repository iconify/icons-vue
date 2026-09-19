<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqx0q-9fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oqx0q-9fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:headphones" /></template>
