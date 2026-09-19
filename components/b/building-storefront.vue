<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3p24nbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3p24nbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:building-storefront" /></template>
