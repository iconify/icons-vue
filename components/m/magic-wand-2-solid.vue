<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehlrt2nct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehlrt2nct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:magic-wand-2-solid" /></template>
