<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdir-06ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdir-06ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-plus" /></template>
