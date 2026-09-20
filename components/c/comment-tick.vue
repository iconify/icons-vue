<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzizi45yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzizi45yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-tick" /></template>
