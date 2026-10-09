<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbr1c2bcx.css';
import '../../css/b/b-mh2-9jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hbr1c2bcx"/><path class="b-mh2-9jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eraser-20-bold" /></template>
