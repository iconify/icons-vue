<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf4d2jblq.css';
import '../../css/t/tmmpscb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gf4d2jblq"/><path class="tmmpscb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desertification-20" /></template>
