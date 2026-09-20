<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcbrlz6ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcbrlz6ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:insert-column-left" /></template>
