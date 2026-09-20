<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl5vce1kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl5vce1kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:koyeb" /></template>
