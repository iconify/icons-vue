<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjtxg3s9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjtxg3s9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:battery-horizontal-full" /></template>
