<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey_z6rmmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey_z6rmmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:label-important" /></template>
