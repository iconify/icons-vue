<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9hvhxbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9hvhxbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-up-wide-narrow-line" /></template>
