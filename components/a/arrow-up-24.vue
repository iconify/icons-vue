<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgsioskge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgsioskge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-up-24" /></template>
