<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8hnh8gme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8hnh8gme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-slash" /></template>
