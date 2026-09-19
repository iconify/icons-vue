<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_r4um0nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_r4um0nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:eject" /></template>
