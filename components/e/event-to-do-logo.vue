<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w448sbksz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w448sbksz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:event-to-do-logo" /></template>
