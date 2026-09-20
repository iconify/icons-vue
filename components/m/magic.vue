<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol409_bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1.5};
const content = `<path class="ol409_bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:magic" /></template>
