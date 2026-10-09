<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5zkycj1r.css';
import '../../css/u/uwnsfhbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j5zkycj1r"/><path class="uwnsfhbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cast-48" /></template>
