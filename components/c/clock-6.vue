<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea6dmxbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea6dmxbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clock-6" /></template>
