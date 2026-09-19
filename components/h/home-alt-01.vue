<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7f1g37vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7f1g37vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:home-alt-01" /></template>
