<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsot7ab7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsot7ab7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:law-24" /></template>
