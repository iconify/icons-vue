<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8ek9lc9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s8ek9lc9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:battery-empty" /></template>
