<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr4n_ac6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr4n_ac6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-bar-vertical-24" /></template>
