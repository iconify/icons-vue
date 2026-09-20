<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln7zp9bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln7zp9bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrows-left" /></template>
