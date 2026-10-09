<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkj35abos.css';
import '../../css/f/f_p8gj0ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jkj35abos"/><path class="f_p8gj0ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:magnet-20-bold" /></template>
