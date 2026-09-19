<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g62_debmy.css';
import '../../css/g/gx4l6kh5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g62_debmy"/><path class="gx4l6kh5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:baseball" /></template>
