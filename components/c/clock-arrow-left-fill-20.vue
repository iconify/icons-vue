<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj2-olrwi.css';
import '../../css/i/ii3oq8bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bj2-olrwi"/><path class="ii3oq8bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-arrow-left-fill-20" /></template>
