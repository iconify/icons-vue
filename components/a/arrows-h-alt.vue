<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl0-7sbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl0-7sbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrows-h-alt" /></template>
