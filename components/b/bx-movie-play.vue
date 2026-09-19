<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o77mreb4u.css';
import '../../css/l/ljorwac7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o77mreb4u"/><path class="ljorwac7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-movie-play" /></template>
