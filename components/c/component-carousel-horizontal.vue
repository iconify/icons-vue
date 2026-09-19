<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykp-s9b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ykp-s9b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:component-carousel-horizontal" /></template>
