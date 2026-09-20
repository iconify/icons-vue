<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-86ihbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-86ihbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-tool-pencil-ruler" /></template>
