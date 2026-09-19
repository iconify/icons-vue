<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umjj1fa5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umjj1fa5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-hold-ease-out-filled" /></template>
