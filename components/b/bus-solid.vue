<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iloufra8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iloufra8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bus-solid" /></template>
