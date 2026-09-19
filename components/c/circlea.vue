<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kihavfb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kihavfb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlea" /></template>
