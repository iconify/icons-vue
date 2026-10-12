<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlijh8b1j.css';
import '../../css/i/ii3oq8bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zlijh8b1j"/><path class="ii3oq8bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-arrow-right-fill-20" /></template>
