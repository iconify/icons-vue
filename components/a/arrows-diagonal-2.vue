<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9q90qrgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9q90qrgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-diagonal-2" /></template>
