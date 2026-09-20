<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff589ackz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff589ackz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-15-fill" /></template>
