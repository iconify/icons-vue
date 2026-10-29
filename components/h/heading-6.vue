<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci2_dx6ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci2_dx6ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-6" /></template>
