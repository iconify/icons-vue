<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcd7ccb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcd7ccb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-left-circle-line" /></template>
