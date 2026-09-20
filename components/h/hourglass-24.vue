<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em0dgkbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em0dgkbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:hourglass-24" /></template>
