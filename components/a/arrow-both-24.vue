<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhn8gh6nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhn8gh6nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-both-24" /></template>
