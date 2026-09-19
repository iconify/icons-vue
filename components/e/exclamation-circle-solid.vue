<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev7dl1b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ev7dl1b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:exclamation-circle-solid" /></template>
