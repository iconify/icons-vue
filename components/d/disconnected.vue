<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u14cn0bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="u14cn0bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:disconnected" /></template>
