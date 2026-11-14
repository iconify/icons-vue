<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3bj8rb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3bj8rb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:chromecast" /></template>
