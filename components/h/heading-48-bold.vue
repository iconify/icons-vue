<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycu86rb2t.css';
import '../../css/m/my-nawb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ycu86rb2t"/><path class="my-nawb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heading-48-bold" /></template>
