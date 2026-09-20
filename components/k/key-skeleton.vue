<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8up9o8ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8up9o8ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:key-skeleton" /></template>
