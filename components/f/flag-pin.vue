<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk7w6qbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk7w6qbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-pin" /></template>
