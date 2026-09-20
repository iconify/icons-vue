<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvuozgpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwvuozgpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:keyframe-align-vertical" /></template>
