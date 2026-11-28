<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvc5jnbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvc5jnbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chart-increasing" /></template>
