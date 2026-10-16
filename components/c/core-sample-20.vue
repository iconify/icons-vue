<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm7hjkbca.css';
import '../../css/b/bnwm9wbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fm7hjkbca"/><path class="bnwm9wbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:core-sample-20" /></template>
