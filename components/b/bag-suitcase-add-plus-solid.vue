<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cprchxb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cprchxb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bag-suitcase-add-plus-solid" /></template>
