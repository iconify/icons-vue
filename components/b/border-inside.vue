<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gurdcvgjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gurdcvgjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-inside" /></template>
