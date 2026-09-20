<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0p0e8b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0p0e8b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:keyframe" /></template>
