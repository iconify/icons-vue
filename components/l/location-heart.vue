<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzp6zjg4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzp6zjg4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-heart" /></template>
