<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez4nq7t0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ez4nq7t0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-euro-16-solid" /></template>
