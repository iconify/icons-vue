<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv0bqvbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv0bqvbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:egg" /></template>
