<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrz7kf1gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrz7kf1gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:crown-light" /></template>
