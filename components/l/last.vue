<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3z5x8z7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="m3z5x8z7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:last" /></template>
