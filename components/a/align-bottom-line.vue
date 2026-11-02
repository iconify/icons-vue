<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghams4dxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghams4dxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-bottom-line" /></template>
