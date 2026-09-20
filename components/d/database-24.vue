<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgu-0nbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgu-0nbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:database-24" /></template>
