<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6feayb0f.css';
import '../../css/p/pi921jb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v6feayb0f"/><path class="pi921jb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ear-defenders-48-bold" /></template>
