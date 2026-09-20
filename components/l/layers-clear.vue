<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft1i4rbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft1i4rbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:layers-clear" /></template>
