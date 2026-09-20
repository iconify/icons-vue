<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5q01fe6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5q01fe6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:link-tiny-expressive" /></template>
