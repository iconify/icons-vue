<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy8l_xb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uy8l_xb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:credit-card-solid" /></template>
