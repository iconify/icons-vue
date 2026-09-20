<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/homf0vbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="homf0vbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:facebook" /></template>
