<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xerq-bbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xerq-bbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contacts-book-3-line" /></template>
