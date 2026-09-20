<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szb4ptbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="szb4ptbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:edit-image" /></template>
