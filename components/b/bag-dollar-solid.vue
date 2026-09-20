<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr3g4wqkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr3g4wqkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bag-dollar-solid" /></template>
