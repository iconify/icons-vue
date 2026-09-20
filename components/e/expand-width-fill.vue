<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn5s1xbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn5s1xbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-width-fill" /></template>
