<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf0ymuc-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf0ymuc-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:loader" /></template>
