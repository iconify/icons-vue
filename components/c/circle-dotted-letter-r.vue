<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eels3fblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eels3fblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-r" /></template>
