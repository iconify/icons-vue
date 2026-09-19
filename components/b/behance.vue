<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv82ee2qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv82ee2qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:behance" /></template>
