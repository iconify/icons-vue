<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enh0vvopo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enh0vvopo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:coffee" /></template>
