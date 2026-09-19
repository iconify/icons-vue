<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfjiz2bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfjiz2bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:css-solid" /></template>
