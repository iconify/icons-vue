<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj2-olrwi.css';
import '../../css/z/z-s_bkbrl.css';
import '../../css/u/uus2tq10l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bj2-olrwi"/><path class="z-s_bkbrl"/><path class="uus2tq10l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-arrow-left-stroke-20" /></template>
