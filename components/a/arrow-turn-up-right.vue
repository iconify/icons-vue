<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvs4msbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvs4msbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-turn-up-right" /></template>
