<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywvmuh6-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywvmuh6-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fridge-round" /></template>
