<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd7m4fbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd7m4fbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-off" /></template>
