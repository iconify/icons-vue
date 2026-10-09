<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk8kloxbh.css';
import '../../css/w/whglv-b6c.css';
import '../../css/t/tn9fdubiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jk8kloxbh"/><path class="whglv-b6c"/><path class="tn9fdubiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-plus-20" /></template>
