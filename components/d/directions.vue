<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqs2jsb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqs2jsb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:directions" /></template>
