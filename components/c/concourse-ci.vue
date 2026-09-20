<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2-390bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2-390bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:concourse-ci" /></template>
