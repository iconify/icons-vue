<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewe7up6bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewe7up6bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:currency-dollar" /></template>
