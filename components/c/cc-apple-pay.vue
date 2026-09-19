<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvzym5b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="nvzym5b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cc-apple-pay" /></template>
