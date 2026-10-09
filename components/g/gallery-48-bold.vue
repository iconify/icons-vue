<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p96uvcb3z.css';
import '../../css/h/hpajvh8ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p96uvcb3z"/><path class="hpajvh8ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gallery-48-bold" /></template>
