<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0ii7tboz.css';
import '../../css/m/myf9c9bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z0ii7tboz"/><path class="myf9c9bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:copper-20" /></template>
