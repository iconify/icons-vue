<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3hes8tqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3hes8tqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-top-right-on-square-solid" /></template>
