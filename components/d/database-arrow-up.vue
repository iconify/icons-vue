<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v52curbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v52curbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:database-arrow-up" /></template>
