<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2pr8qhck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2pr8qhck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:egg-filled" /></template>
