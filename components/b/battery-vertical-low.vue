<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw3l99b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cw3l99b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:battery-vertical-low" /></template>
