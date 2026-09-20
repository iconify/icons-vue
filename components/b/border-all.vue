<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw1dj155k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw1dj155k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:border-all" /></template>
