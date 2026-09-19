<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1whnlu7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1whnlu7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:3sat" /></template>
