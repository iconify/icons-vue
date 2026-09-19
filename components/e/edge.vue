<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0tqwu5bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0tqwu5bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:edge" /></template>
