<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thh976iif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thh976iif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ladder" /></template>
