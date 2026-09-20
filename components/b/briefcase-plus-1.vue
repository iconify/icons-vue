<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3fg58wzn.css';
import '../../css/g/g_zluxtrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="u3fg58wzn"/><path class="g_zluxtrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:briefcase-plus-1" /></template>
