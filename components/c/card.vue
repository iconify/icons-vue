<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc9bi-5wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hc9bi-5wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:card" /></template>
