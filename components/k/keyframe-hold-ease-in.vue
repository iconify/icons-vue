<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqytk241q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqytk241q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-hold-ease-in" /></template>
