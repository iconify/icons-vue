<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4pa64bjg.css';
import '../../css/b/banax9p2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i4pa64bjg"/><path class="banax9p2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bread-20" /></template>
