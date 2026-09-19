<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm5yisb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm5yisb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bowl-rice" /></template>
