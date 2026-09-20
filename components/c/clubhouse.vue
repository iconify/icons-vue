<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba-t9briz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba-t9briz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:clubhouse" /></template>
