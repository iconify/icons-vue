<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0nlblb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="v0nlblb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:euro" /></template>
