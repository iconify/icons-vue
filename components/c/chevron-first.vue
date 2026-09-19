<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3f3pabut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3f3pabut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevron-first" /></template>
