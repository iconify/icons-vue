<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mco0w3z_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mco0w3z_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:attachment-3-fill" /></template>
