<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya6h9sbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya6h9sbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:fast-forward-circle" /></template>
