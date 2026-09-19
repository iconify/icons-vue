<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqf-rnkzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iqf-rnkzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-small-down-solid" /></template>
