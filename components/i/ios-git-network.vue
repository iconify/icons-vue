<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myq2e5yds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="myq2e5yds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-git-network" /></template>
