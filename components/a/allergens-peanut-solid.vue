<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynao2ccsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ynao2ccsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:allergens-peanut-solid" /></template>
