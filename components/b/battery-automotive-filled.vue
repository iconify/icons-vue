<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q49xp1buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q49xp1buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-automotive-filled" /></template>
