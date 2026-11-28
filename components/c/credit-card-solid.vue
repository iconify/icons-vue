<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/errg8-z4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="errg8-z4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:credit-card-solid" /></template>
