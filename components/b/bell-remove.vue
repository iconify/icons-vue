<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caz0ggb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caz0ggb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-remove" /></template>
