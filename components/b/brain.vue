<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp9bf8b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="rp9bf8b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brain" /></template>
