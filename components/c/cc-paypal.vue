<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9ml06bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="c9ml06bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cc-paypal" /></template>
