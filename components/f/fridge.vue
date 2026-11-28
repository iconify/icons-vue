<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9y-kw0_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9y-kw0_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fridge" /></template>
