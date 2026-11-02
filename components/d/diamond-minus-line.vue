<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcn5b1kkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcn5b1kkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diamond-minus-line" /></template>
