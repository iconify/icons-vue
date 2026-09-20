<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhih48bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhih48bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hypothesis" /></template>
