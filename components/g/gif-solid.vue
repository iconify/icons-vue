<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyxqmouzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vyxqmouzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:gif-solid" /></template>
