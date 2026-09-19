<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpn9qcb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpn9qcb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-hold-ease-in-filled" /></template>
