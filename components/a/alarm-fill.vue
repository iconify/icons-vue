<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1pz5ebrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1pz5ebrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:alarm-fill" /></template>
