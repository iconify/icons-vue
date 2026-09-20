<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc8aybcmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uc8aybcmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:allergens-fish-remix" /></template>
