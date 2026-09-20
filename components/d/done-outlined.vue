<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2a3ezblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2a3ezblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:done-outlined" /></template>
