<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j39z0vbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j39z0vbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amd" /></template>
