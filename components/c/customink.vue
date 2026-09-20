<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i20v4--ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i20v4--ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:customink" /></template>
