<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw7xd7oft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw7xd7oft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:centris" /></template>
