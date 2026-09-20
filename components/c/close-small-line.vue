<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gma0z2bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gma0z2bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-small-line" /></template>
