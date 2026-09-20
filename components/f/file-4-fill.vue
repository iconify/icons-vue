<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjk8aukoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjk8aukoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-4-fill" /></template>
