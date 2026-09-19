<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6kakubol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6kakubol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:heart-thin" /></template>
