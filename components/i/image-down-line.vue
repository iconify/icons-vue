<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5e_d4lum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5e_d4lum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-down-line" /></template>
