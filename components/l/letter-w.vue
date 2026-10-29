<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bba0mwb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bba0mwb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-w" /></template>
