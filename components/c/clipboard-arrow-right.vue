<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcx7yod2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcx7yod2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-arrow-right" /></template>
