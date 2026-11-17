<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsb9vacax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsb9vacax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bot-minus" /></template>
