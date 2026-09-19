<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8jeuacsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p8jeuacsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:currency-bangladeshi" /></template>
