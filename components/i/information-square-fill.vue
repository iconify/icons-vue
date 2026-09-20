<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzl2uackh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzl2uackh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:information-square-fill" /></template>
