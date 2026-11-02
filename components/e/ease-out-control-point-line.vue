<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f94_otbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f94_otbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-out-control-point-line" /></template>
