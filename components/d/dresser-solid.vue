<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f53sku4ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f53sku4ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dresser-solid" /></template>
