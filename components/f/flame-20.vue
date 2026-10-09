<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilf28rb4r.css';
import '../../css/r/rilm8wbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ilf28rb4r"/><path class="rilm8wbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flame-20" /></template>
