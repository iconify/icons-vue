<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhxdghb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhxdghb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:equal-not-duocolor-round" /></template>
