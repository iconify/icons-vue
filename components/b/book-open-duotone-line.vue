<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt4g3v8ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt4g3v8ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:book-open-duotone-line" /></template>
