<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2ljbc5we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2ljbc5we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gallery3" /></template>
