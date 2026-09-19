<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4116or5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4116or5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-bangladeshi" /></template>
