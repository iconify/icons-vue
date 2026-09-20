<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o13tqh8vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o13tqh8vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-2-fill" /></template>
