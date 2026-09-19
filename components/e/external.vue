<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxp1jqbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxp1jqbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:external" /></template>
