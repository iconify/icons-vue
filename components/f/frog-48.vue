<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cifz9-27c.css';
import '../../css/w/w1o4mgb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cifz9-27c"/><path class="w1o4mgb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frog-48" /></template>
