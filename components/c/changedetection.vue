<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5su30b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5su30b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:changedetection" /></template>
