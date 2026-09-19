<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4ed2vbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4ed2vbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-pound-solid" /></template>
