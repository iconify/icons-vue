<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujilh4b6o.css';
import '../../css/q/q9et3dbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ujilh4b6o"/><path class="q9et3dbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bandage-20-bold" /></template>
