<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd5w4cckj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kd5w4cckj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-round-outline" /></template>
