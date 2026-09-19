<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcwyqgoyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vcwyqgoyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-right-solid" /></template>
