<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnt5nqbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnt5nqbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:add-row" /></template>
