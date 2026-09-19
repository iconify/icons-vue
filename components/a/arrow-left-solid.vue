<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg_hf-5gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mg_hf-5gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-solid" /></template>
