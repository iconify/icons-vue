<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msawb0uon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="msawb0uon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bookmark-minus-f" /></template>
