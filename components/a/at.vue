<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgc_t5b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgc_t5b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:at" /></template>
