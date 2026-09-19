<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8lhuhb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s8lhuhb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:load-c" /></template>
