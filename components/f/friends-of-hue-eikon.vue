<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l101v0bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l101v0bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:friends-of-hue-eikon" /></template>
