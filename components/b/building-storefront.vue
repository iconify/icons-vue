<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvyycz-af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvyycz-af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-storefront" /></template>
