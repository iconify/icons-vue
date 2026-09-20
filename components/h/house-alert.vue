<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bis6ikbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bis6ikbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-alert" /></template>
