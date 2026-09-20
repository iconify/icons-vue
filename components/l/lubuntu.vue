<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqrsj0b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqrsj0b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lubuntu" /></template>
