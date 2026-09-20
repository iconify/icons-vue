<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk6mc0bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk6mc0bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right-bold" /></template>
