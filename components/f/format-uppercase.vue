<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp_3u9b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp_3u9b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-uppercase" /></template>
