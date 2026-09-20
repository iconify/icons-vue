<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv04xxbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv04xxbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codefresh" /></template>
