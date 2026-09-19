<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_mdh6bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_mdh6bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-4-square-fill" /></template>
