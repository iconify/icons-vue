<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y85bi0b7a.css';
import '../../css/q/q3818dbqt.css';
import '../../css/f/fbiyt7hbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y85bi0b7a"/><path class="q3818dbqt"/><path class="fbiyt7hbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drawing-compass-20" /></template>
