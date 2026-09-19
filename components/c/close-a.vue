<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgci3mbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgci3mbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:close-a" /></template>
