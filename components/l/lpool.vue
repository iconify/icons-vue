<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj38x5bhy.css';
import '../../css/j/jd18gacdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj38x5bhy"/><path class="jd18gacdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lpool" /></template>
