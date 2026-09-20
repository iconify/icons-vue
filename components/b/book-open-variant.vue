<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-89dhvje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-89dhvje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-open-variant" /></template>
