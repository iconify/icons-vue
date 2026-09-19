<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekk48rbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekk48rbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:arrow-right" /></template>
