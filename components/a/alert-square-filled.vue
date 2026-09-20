<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdwtbc9eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdwtbc9eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-square-filled" /></template>
