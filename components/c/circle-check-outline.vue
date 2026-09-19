<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2sf6sbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2sf6sbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:circle-check-outline" /></template>
