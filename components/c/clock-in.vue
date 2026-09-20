<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enhjo2bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enhjo2bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-in" /></template>
