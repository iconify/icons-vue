<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx-pl7guj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx-pl7guj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-undo-down-right" /></template>
