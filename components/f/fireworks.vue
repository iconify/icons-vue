<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a90eyi3wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a90eyi3wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fireworks" /></template>
