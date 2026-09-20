<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp9b6lb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp9b6lb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:brightness-high" /></template>
