<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0l5f0mlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0l5f0mlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:caret-right-duotone" /></template>
