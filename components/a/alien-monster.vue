<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aadf2yd4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="aadf2yd4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:alien-monster" /></template>
