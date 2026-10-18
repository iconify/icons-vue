<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l34wzp3oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l34wzp3oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:chromecast" /></template>
