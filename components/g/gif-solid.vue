<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro2bxgb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ro2bxgb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gif-solid" /></template>
