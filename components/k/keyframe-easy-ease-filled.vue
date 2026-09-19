<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5jsh8avv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5jsh8avv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-easy-ease-filled" /></template>
