<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frgp4ccef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frgp4ccef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:contacts-line" /></template>
