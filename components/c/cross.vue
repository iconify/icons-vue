<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta083pgpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta083pgpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cross" /></template>
