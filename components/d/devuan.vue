<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejwoa9bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejwoa9bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:devuan" /></template>
