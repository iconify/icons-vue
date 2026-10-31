<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdjscxbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdjscxbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-round" /></template>
