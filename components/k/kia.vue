<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7p3tpizi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7p3tpizi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kia" /></template>
