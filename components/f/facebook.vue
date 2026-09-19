<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as-y2437r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as-y2437r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:facebook" /></template>
