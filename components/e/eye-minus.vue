<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2z5eczhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2z5eczhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eye-minus" /></template>
