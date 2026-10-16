<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_bbmbbxq.css';
import '../../css/b/b9xdq3bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c_bbmbbxq"/><path class="b9xdq3bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-joint-20" /></template>
