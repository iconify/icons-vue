<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy4b1wx4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy4b1wx4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cake-variant" /></template>
