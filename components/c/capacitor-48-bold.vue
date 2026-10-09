<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j93ektbkr.css';
import '../../css/z/zf5iukb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j93ektbkr"/><path class="zf5iukb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:capacitor-48-bold" /></template>
