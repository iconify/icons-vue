<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6dknbc5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":377,"height":512};
const content = `<path class="w6dknbc5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lsl" /></template>
