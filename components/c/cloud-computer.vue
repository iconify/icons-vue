<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjnz9-bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjnz9-bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cloud-computer" /></template>
