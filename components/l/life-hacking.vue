<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_fv_k1pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_fv_k1pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:life-hacking" /></template>
