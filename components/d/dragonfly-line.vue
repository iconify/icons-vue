<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g61lc6tkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g61lc6tkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dragonfly-line" /></template>
