<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-k14bb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-k14bb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:flag" /></template>
