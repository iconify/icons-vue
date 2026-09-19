<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h505gmbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h505gmbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hdmi" /></template>
