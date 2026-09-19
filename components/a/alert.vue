<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5rnco5yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f5rnco5yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:alert" /></template>
