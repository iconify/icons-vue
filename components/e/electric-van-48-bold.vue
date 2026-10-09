<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il6d4vbnm.css';
import '../../css/o/o244yobqh.css';
import '../../css/d/d39zil3no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="il6d4vbnm"/><path class="o244yobqh"/><path class="d39zil3no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-van-48-bold" /></template>
